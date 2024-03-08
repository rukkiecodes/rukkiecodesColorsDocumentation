<template>
    <h3 class="mt-10">Green</h3>
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
                <td>{{ green50.name }}</td>
                <td>{{ green50.hex }}</td>
                <td>
                    <v-sheet :color="green50.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ green100.name }}</td>
                <td>{{ green100.hex }}</td>
                <td>
                    <v-sheet :color="green100.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ green200.name }}</td>
                <td>{{ green200.hex }}</td>
                <td>
                    <v-sheet :color="green200.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ green300.name }}</td>
                <td>{{ green300.hex }}</td>
                <td>
                    <v-sheet :color="green300.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ green400.name }}</td>
                <td>{{ green400.hex }}</td>
                <td>
                    <v-sheet :color="green400.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ green500.name }}</td>
                <td>{{ green500.hex }}</td>
                <td>
                    <v-sheet :color="green500.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ green600.name }}</td>
                <td>{{ green600.hex }}</td>
                <td>
                    <v-sheet :color="green600.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ green700.name }}</td>
                <td>{{ green700.hex }}</td>
                <td>
                    <v-sheet :color="green700.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ green800.name }}</td>
                <td>{{ green800.hex }}</td>
                <td>
                    <v-sheet :color="green800.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ green900.name }}</td>
                <td>{{ green900.hex }}</td>
                <td>
                    <v-sheet :color="green900.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
        </tbody>
    </v-table>
</template>



<script setup>
import {
    green50,
    green100,
    green200,
    green300,
    green400,
    green500,
    green600,
    green700,
    green800,
    green900,
} from 'rukkiecodes-colors';
</script>
