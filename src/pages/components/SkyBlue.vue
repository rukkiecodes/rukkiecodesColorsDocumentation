<template>
    <h3 class="mt-10">Sky Blue</h3>
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
                <td>{{ skyBlue50.name }}</td>
                <td>{{ skyBlue50.hex }}</td>
                <td>
                    <v-sheet :color="skyBlue50.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ skyBlue100.name }}</td>
                <td>{{ skyBlue100.hex }}</td>
                <td>
                    <v-sheet :color="skyBlue100.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ skyBlue200.name }}</td>
                <td>{{ skyBlue200.hex }}</td>
                <td>
                    <v-sheet :color="skyBlue200.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ skyBlue300.name }}</td>
                <td>{{ skyBlue300.hex }}</td>
                <td>
                    <v-sheet :color="skyBlue300.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ skyBlue400.name }}</td>
                <td>{{ skyBlue400.hex }}</td>
                <td>
                    <v-sheet :color="skyBlue400.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ skyBlue500.name }}</td>
                <td>{{ skyBlue500.hex }}</td>
                <td>
                    <v-sheet :color="skyBlue500.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ skyBlue600.name }}</td>
                <td>{{ skyBlue600.hex }}</td>
                <td>
                    <v-sheet :color="skyBlue600.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ skyBlue700.name }}</td>
                <td>{{ skyBlue700.hex }}</td>
                <td>
                    <v-sheet :color="skyBlue700.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ skyBlue800.name }}</td>
                <td>{{ skyBlue800.hex }}</td>
                <td>
                    <v-sheet :color="skyBlue800.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ skyBlue900.name }}</td>
                <td>{{ skyBlue900.hex }}</td>
                <td>
                    <v-sheet :color="skyBlue900.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
        </tbody>
    </v-table>
</template>



<script setup>
import {
    skyBlue50,
    skyBlue100,
    skyBlue200,
    skyBlue300,
    skyBlue400,
    skyBlue500,
    skyBlue600,
    skyBlue700,
    skyBlue800,
    skyBlue900,
} from 'rukkiecodes-colors';
</script>
