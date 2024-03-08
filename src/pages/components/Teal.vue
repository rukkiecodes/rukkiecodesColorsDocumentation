<template>
    <h3 class="mt-10">Teal</h3>
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
                <td>{{ teal50.name }}</td>
                <td>{{ teal50.hex }}</td>
                <td>
                    <v-sheet :color="teal50.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ teal100.name }}</td>
                <td>{{ teal100.hex }}</td>
                <td>
                    <v-sheet :color="teal100.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ teal200.name }}</td>
                <td>{{ teal200.hex }}</td>
                <td>
                    <v-sheet :color="teal200.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ teal300.name }}</td>
                <td>{{ teal300.hex }}</td>
                <td>
                    <v-sheet :color="teal300.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ teal400.name }}</td>
                <td>{{ teal400.hex }}</td>
                <td>
                    <v-sheet :color="teal400.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ teal500.name }}</td>
                <td>{{ teal500.hex }}</td>
                <td>
                    <v-sheet :color="teal500.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ teal600.name }}</td>
                <td>{{ teal600.hex }}</td>
                <td>
                    <v-sheet :color="teal600.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ teal700.name }}</td>
                <td>{{ teal700.hex }}</td>
                <td>
                    <v-sheet :color="teal700.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ teal800.name }}</td>
                <td>{{ teal800.hex }}</td>
                <td>
                    <v-sheet :color="teal800.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ teal900.name }}</td>
                <td>{{ teal900.hex }}</td>
                <td>
                    <v-sheet :color="teal900.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
        </tbody>
    </v-table>
</template>



<script setup>
import {
    teal50,
    teal100,
    teal200,
    teal300,
    teal400,
    teal500,
    teal600,
    teal700,
    teal800,
    teal900,
} from 'rukkiecodes-colors';
</script>
