<template>
    <h3 class="mt-10">Yellow</h3>
    <v-table>
        <thead>
            <tr>
                <th class="text-left">
                    Name
                </th>
                <th class="text-left">
                    Code
                </th>
                <th class="text-left">
                    Sample
                </th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>{{ yellow50.name }}</td>
                <td>{{ yellow50.hex }}</td>
                <td>
                    <v-sheet :color="yellow50.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ yellow100.name }}</td>
                <td>{{ yellow100.hex }}</td>
                <td>
                    <v-sheet :color="yellow100.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ yellow200.name }}</td>
                <td>{{ yellow200.hex }}</td>
                <td>
                    <v-sheet :color="yellow200.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ yellow300.name }}</td>
                <td>{{ yellow300.hex }}</td>
                <td>
                    <v-sheet :color="yellow300.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ yellow400.name }}</td>
                <td>{{ yellow400.hex }}</td>
                <td>
                    <v-sheet :color="yellow400.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ yellow500.name }}</td>
                <td>{{ yellow500.hex }}</td>
                <td>
                    <v-sheet :color="yellow500.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ yellow600.name }}</td>
                <td>{{ yellow600.hex }}</td>
                <td>
                    <v-sheet :color="yellow600.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ yellow700.name }}</td>
                <td>{{ yellow700.hex }}</td>
                <td>
                    <v-sheet :color="yellow700.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ yellow800.name }}</td>
                <td>{{ yellow800.hex }}</td>
                <td>
                    <v-sheet :color="yellow800.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ yellow900.name }}</td>
                <td>{{ yellow900.hex }}</td>
                <td>
                    <v-sheet :color="yellow900.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
        </tbody>
    </v-table>
</template>



<script setup>
import {
    yellow50,
    yellow100,
    yellow200,
    yellow300,
    yellow400,
    yellow500,
    yellow600,
    yellow700,
    yellow800,
    yellow900,
} from 'rukkiecodes-colors';
</script>
